<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/anel9tbgf.css';
import '../../css/c/c11okoi4v.css';
import '../../css/t/tyrt-db1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="anel9tbgf"/><path class="c11okoi4v"/><path class="tyrt-db1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clover-duotone" /></template>
