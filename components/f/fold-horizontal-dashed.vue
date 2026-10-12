<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/binn1sb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="binn1sb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:fold-horizontal-dashed" /></template>
