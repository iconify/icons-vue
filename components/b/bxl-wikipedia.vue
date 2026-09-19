<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv3kprbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv3kprbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-wikipedia" /></template>
