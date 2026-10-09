<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxbs21b9m.css';
import '../../css/c/ckdcb_lym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zxbs21b9m"/><path class="ckdcb_lym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:id-card-48" /></template>
