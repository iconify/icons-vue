<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khu5r_tqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khu5r_tqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cube-solid" /></template>
