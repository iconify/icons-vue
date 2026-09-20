<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce1h9l8wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce1h9l8wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cursor-default-gesture-outline" /></template>
