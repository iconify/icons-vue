<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv2_4wbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv2_4wbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-3-line" /></template>
