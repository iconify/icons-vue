<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j96ro8ect.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j96ro8ect"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dice-5-outline" /></template>
