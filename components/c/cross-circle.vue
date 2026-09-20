<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuedu7c-d.css';
import '../../css/m/mf98adcos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kuedu7c-d"/><path class="mf98adcos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cross-circle" /></template>
