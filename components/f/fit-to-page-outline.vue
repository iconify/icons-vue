<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skuz2sbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skuz2sbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fit-to-page-outline" /></template>
