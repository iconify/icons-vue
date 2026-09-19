<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka_vtlb8j.css';
import '../../css/c/ckzloge-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ka_vtlb8j"/><path class="ckzloge-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:list-high-priority" /></template>
