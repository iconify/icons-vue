<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca-ltmebp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca-ltmebp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-40-bluetooth" /></template>
