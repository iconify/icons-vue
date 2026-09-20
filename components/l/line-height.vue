<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svb_ag-kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="svb_ag-kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:line-height" /></template>
