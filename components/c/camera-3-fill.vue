<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hty2abc4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hty2abc4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:camera-3-fill" /></template>
