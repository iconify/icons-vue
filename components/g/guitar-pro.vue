<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5w6t-_yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5w6t-_yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:guitar-pro" /></template>
