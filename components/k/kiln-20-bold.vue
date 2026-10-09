<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_-k_fetr.css';
import '../../css/l/l7hzbkbbx.css';
import '../../css/l/lr1_aeb-h.css';
import '../../css/y/yccprlbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m_-k_fetr"/><path class="l7hzbkbbx"/><path class="lr1_aeb-h"/><path class="yccprlbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kiln-20-bold" /></template>
