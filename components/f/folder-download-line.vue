<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibdr8ccft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibdr8ccft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-download-line" /></template>
