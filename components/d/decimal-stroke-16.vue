<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy1re-qcg.css';
import '../../css/l/lodosdbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<ellipse class="qy1re-qcg"/><circle class="lodosdbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:decimal-stroke-16" /></template>
