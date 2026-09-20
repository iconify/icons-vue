<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwuz2mi4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwuz2mi4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-off-outline" /></template>
