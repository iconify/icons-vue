<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te48i79xt.css';
import '../../css/s/syysw3b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="te48i79xt"/><path class="syysw3b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crucible-48" /></template>
