<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk2-5tbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk2-5tbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:border-bottom" /></template>
