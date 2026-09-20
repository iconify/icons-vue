<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d07mmikoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d07mmikoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:add-call" /></template>
