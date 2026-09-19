<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1420tb-x.css';
import '../../css/o/o2k0j_bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<rect class="d1420tb-x"/><path class="o2k0j_bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:credit-card-stroke-12" /></template>
