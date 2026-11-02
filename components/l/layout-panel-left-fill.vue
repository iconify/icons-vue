<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x58o06ccs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x58o06ccs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-panel-left-fill" /></template>
