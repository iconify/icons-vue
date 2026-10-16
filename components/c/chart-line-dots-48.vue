<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utf77lbef.css';
import '../../css/b/bm1aiubys.css';
import '../../css/h/h6bsihbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="utf77lbef"/><path class="bm1aiubys"/><path class="h6bsihbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-line-dots-48" /></template>
