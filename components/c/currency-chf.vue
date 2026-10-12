<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxdycwq-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxdycwq-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:currency-chf" /></template>
