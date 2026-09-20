<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl1x_9bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl1x_9bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ball-pen-line" /></template>
