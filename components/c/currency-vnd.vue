<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf0p-ybka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf0p-ybka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:currency-vnd" /></template>
