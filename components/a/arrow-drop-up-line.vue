<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhlsyklwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhlsyklwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-drop-up-line" /></template>
