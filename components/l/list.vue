<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dba1-yhnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dba1-yhnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:list" /></template>
