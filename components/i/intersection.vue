<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lok2q1_vw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lok2q1_vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:intersection" /></template>
