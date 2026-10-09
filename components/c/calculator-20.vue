<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1oyp4uhi.css';
import '../../css/q/qyfd5ps_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b1oyp4uhi"/><path class="qyfd5ps_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calculator-20" /></template>
