<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb-ee9b3j.css';
import '../../css/b/bwcanry2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb-ee9b3j"/><path class="bwcanry2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:caret-left-square" /></template>
