<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgygvbmub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgygvbmub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-video-solid" /></template>
