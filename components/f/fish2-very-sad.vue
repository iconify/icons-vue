<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn7foxpmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sn7foxpmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:fish2-very-sad" /></template>
