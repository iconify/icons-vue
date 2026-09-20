<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f77jxdb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f77jxdb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bnb-chain" /></template>
