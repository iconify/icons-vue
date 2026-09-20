<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noub0abmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noub0abmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:album-line" /></template>
