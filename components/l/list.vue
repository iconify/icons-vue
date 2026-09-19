<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vbahp1bvw.css';
import '../../css/f/f-auj7bix.css';
import '../../css/o/o0dq1pbzh.css';
import '../../css/t/tcbvmfb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><circle class="vbahp1bvw"/><circle class="f-auj7bix"/><circle class="o0dq1pbzh"/><path class="tcbvmfb_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:list" /></template>
