<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt_dwfbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pt_dwfbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:cotton-bureau" /></template>
