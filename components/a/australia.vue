<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl8x224tx.css';
import '../../css/w/ww52sv46j.css';
import '../../css/n/nv4ztabcc.css';
import '../../css/o/o6rwwebbc.css';
import '../../css/u/ufzh-1jpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="yl8x224tx"/><path class="ww52sv46j"/><path class="nv4ztabcc"/><path class="o6rwwebbc"/><path class="ufzh-1jpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:australia" /></template>
