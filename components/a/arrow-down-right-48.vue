<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpcpxlb-i.css';
import '../../css/b/bwf-mg5sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gpcpxlb-i"/><path class="bwf-mg5sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-down-right-48" /></template>
