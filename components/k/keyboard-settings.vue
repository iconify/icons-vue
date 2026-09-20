<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf3ag-ppl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf3ag-ppl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-settings" /></template>
