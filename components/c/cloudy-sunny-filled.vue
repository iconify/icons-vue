<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgm2whbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgm2whbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:cloudy-sunny-filled" /></template>
