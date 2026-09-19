<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp2nw3bpc.css';
import '../../css/k/k-8iobcst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bp2nw3bpc"/><path class="k-8iobcst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bar-chart-sharp" /></template>
