<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am1jjgb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am1jjgb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-location" /></template>
