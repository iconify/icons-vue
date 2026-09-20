<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uma6umd4x.css';
import '../../css/u/ua-paobrh.css';
import '../../css/x/xe0_hsbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uma6umd4x"/><path class="ua-paobrh"/><path class="xe0_hsbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:apk-1-bold" /></template>
