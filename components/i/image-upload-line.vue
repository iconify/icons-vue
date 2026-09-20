<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwmj_e-pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwmj_e-pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:image-upload-line" /></template>
