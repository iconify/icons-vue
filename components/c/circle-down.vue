<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrbpuobsp.css';
import '../../css/a/a_k2ufbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mrbpuobsp"/><path class="a_k2ufbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:circle-down" /></template>
