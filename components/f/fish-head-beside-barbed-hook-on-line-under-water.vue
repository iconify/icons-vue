<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seqwugbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="seqwugbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fish-head-beside-barbed-hook-on-line-under-water" /></template>
