<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2u-ycczg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2u-ycczg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:clip-filled" /></template>
