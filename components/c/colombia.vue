<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j648mcboz.css';
import '../../css/i/iiv7b4kfn.css';
import '../../css/j/jggsly9mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="j648mcboz"/><path class="iiv7b4kfn"/><path class="jggsly9mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:colombia" /></template>
