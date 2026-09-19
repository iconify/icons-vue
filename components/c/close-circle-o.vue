<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quuc_sk-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="quuc_sk-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:close-circle-o" /></template>
