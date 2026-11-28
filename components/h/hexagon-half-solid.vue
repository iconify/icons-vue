<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql3-lpzya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql3-lpzya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hexagon-half-solid" /></template>
