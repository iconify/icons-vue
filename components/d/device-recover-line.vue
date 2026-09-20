<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy9o1kbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy9o1kbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:device-recover-line" /></template>
