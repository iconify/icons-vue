<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bllci6bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bllci6bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:broom3-filled" /></template>
