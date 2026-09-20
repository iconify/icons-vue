<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txtpdbbzb.css';
import '../../css/t/t2cfwekii.css';
import '../../css/z/zvi_0b-ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="txtpdbbzb"/><path class="t2cfwekii"/><path class="zvi_0b-ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:datapup" /></template>
