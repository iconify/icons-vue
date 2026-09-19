<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6n_672at.css';
import '../../css/z/zuzne9bcw.css';
import '../../css/i/it7_xub9z.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 u6n_672at"/><path class="clr-i-outline clr-i-outline-path-2 zuzne9bcw"/><path class="clr-i-outline clr-i-outline-path-3 it7_xub9z"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:align-right-line" /></template>
