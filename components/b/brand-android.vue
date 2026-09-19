<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnoynmb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnoynmb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:brand-android" /></template>
