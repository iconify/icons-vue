<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhlhglulc.css';
import '../../css/k/k1nvv5m4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":240,"height":240};
const content = `<path class="fhlhglulc"/><path class="k1nvv5m4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:affinity" /></template>
