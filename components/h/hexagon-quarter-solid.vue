<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5pb54b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5pb54b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hexagon-quarter-solid" /></template>
