<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcd3_ql_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcd3_ql_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-left-sm" /></template>
