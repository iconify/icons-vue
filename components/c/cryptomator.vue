<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0_w6_bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0_w6_bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:cryptomator" /></template>
