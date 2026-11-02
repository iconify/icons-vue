<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs4gddbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs4gddbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:image-upscale-line" /></template>
