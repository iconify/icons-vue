<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrav_bckm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrav_bckm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:home" /></template>
