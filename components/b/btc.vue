<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpeo57y3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tpeo57y3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:btc" /></template>
