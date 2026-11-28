<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0c-0nbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0c-0nbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-left-through-line-solid" /></template>
