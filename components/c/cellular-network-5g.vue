<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbw9buaii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbw9buaii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:cellular-network-5g" /></template>
