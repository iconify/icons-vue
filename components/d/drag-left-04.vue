<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bz0ohmntq.css';
import '../../css/x/xgdp6pb2v.css';
import '../../css/d/dyq4pdb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bz0ohmntq"/><path class="xgdp6pb2v"/><path class="dyq4pdb8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:drag-left-04" /></template>
