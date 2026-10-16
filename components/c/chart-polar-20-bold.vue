<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umayoyb1k.css';
import '../../css/o/ocq2nsbni.css';
import '../../css/z/zr0me355o.css';
import '../../css/b/besblbm2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="umayoyb1k"/><path class="ocq2nsbni"/><path class="zr0me355o"/><path class="besblbm2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-polar-20-bold" /></template>
