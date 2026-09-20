<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tstc3xbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tstc3xbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:fitocracy" /></template>
