<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqpln8bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqpln8bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-3-plus" /></template>
