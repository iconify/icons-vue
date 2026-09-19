<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3i704izb.css';
import '../../css/r/rypnjzb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l3i704izb"/><path class="rypnjzb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:highlight-twotone" /></template>
