<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfoz5e68w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="zfoz5e68w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:handbag" /></template>
