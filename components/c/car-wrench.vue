<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoo82bpzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qoo82bpzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:car-wrench" /></template>
