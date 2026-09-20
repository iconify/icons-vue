<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-1oz4bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="s-1oz4bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:cashier" /></template>
