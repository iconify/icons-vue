<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg41-xbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg41-xbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-group-remove" /></template>
