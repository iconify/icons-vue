<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzmit6bbq.css';
import '../../css/v/vwdgxlbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzmit6bbq"/><path class="vwdgxlbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-layer-plus" /></template>
