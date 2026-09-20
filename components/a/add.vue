<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kymer5dgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kymer5dgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:add" /></template>
