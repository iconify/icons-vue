<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg2bd9-ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zg2bd9-ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:dailymotion-logo-solid" /></template>
