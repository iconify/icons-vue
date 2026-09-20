<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moa9hkbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="moa9hkbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:delete-back-2-line" /></template>
