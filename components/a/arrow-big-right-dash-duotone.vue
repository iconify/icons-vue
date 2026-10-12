<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k8yumab0d.css';
import '../../css/k/k9cfksblu.css';
import '../../css/i/ig4fi3b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k8yumab0d"/><path class="k9cfksblu"/><path class="ig4fi3b7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:arrow-big-right-dash-duotone" /></template>
