<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8xj_quvl.css';
import '../../css/h/hqconcbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h8xj_quvl"/><path class="hqconcbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:kubelet" /></template>
