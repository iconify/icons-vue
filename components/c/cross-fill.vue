<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5ap8fbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5ap8fbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:cross-fill" /></template>
