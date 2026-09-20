<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8vxzdj-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8vxzdj-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-video-line" /></template>
