<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjj_bvboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjj_bvboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bitrise" /></template>
