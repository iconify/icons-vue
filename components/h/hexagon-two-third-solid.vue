<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hddwlbc1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hddwlbc1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hexagon-two-third-solid" /></template>
