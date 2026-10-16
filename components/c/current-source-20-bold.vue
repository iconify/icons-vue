<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1aumdb7c.css';
import '../../css/k/kw01wubkh.css';
import '../../css/w/w0gkibbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i1aumdb7c"/><path class="kw01wubkh"/><path class="w0gkibbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:current-source-20-bold" /></template>
