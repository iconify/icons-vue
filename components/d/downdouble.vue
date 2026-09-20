<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpm3-ysuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="zpm3-ysuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:downdouble" /></template>
