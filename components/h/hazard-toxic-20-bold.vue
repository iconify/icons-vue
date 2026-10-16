<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcia1ds6l.css';
import '../../css/k/k7ts6_btn.css';
import '../../css/q/q5g7_gbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pcia1ds6l"/><path class="k7ts6_btn"/><path class="q5g7_gbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hazard-toxic-20-bold" /></template>
