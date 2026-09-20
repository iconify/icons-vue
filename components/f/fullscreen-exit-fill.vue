<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf9pswoxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf9pswoxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fullscreen-exit-fill" /></template>
