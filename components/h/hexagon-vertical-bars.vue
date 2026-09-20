<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmdj_zw-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hmdj_zw-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:hexagon-vertical-bars" /></template>
