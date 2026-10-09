<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub-di_unr.css';
import '../../css/d/dx_dw6rtl.css';
import '../../css/g/g-5s0nbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ub-di_unr"/><path class="dx_dw6rtl"/><path class="g-5s0nbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloche-48-bold" /></template>
