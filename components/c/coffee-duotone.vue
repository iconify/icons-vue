<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u4d_cbcla.css';
import '../../css/s/smcd-7qqt.css';
import '../../css/b/bqq9k-tbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u4d_cbcla"/><path class="smcd-7qqt"/><path class="bqq9k-tbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:coffee-duotone" /></template>
