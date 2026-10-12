<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsd7icbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsd7icbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:currency-brl" /></template>
