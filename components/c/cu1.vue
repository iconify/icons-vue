<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7ze_xbnd.css';
import '../../css/o/o-ow-2npg.css';
import '../../css/g/godladckq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c7ze_xbnd"/><path class="o-ow-2npg"/><path class="godladckq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cu1" /></template>
