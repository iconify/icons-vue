<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4cxdgfzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":16};
const content = `<path class="w4cxdgfzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:bitcoin" /></template>
