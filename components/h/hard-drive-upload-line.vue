<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8vvg729k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8vvg729k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hard-drive-upload-line" /></template>
