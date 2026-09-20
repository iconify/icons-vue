<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9vzhu_1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9vzhu_1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flashlight-fill" /></template>
