<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2pqw85-k.css';
import '../../css/h/h5hitcc0j.css';
import '../../css/i/i_fu6kg3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d2pqw85-k"/><path class="h5hitcc0j"/><path class="i_fu6kg3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-trading-20-bold" /></template>
