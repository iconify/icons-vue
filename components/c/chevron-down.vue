<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyu6-1wma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyu6-1wma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:chevron-down" /></template>
