<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl7klpbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl7klpbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-wifi-fill" /></template>
