<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg-rq_txf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rg-rq_txf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:dash-fill-12" /></template>
