<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk-jb4_bv.css';
import '../../css/y/yg49weaem.css';
import '../../css/k/kyq-juboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lk-jb4_bv"/><path clip-rule="evenodd" class="yg49weaem"/><path class="kyq-juboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:garage-solid" /></template>
