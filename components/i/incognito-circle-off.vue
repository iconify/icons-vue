<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek6t0acuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek6t0acuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:incognito-circle-off" /></template>
