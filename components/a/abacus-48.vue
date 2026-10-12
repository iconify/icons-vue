<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8jt_mb0e.css';
import '../../css/k/kga35kgyc.css';
import '../../css/z/z5kh--bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k8jt_mb0e"/><path class="kga35kgyc"/><path class="z5kh--bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:abacus-48" /></template>
