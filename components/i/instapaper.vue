<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1_w2zbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1_w2zbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:instapaper" /></template>
