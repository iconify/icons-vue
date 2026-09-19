<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr3llbuao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="wr3llbuao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:calcplus" /></template>
