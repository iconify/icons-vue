<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiv1j9a1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jiv1j9a1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-video-plus" /></template>
