<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6hxv1kmr.css';
import '../../css/m/mmasx843w.css';
import '../../css/d/d1xy-t7vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u6hxv1kmr"/><path class="mmasx843w"/><path class="d1xy-t7vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:loan-20-bold" /></template>
