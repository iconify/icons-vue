<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq8vp4b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq8vp4b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-1-fill" /></template>
