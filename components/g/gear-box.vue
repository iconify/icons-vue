<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noj3-fbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noj3-fbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gear-box" /></template>
