<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an3y2z25r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an3y2z25r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-l-octagon-solid" /></template>
