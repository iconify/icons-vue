<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_g1jwbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_g1jwbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gitee" /></template>
