<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f38xf6bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f38xf6bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-c-hexagon-solid" /></template>
