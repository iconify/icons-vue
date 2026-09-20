<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktxd9qv_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktxd9qv_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:help-box-outline" /></template>
