<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvlax3sde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvlax3sde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-m-box" /></template>
