<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgg6crb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgg6crb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:firefox-browser-fill" /></template>
