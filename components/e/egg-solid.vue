<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5eqpmbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5eqpmbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:egg-solid" /></template>
