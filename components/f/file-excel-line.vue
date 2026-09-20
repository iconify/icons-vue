<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksvfn86nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksvfn86nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-excel-line" /></template>
