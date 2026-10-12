<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucpbrwyid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucpbrwyid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:grip-vertical" /></template>
