<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnx-q8bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnx-q8bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrow-down-line" /></template>
