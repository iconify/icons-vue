<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgo_ukb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dgo_ukb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:contract-exclamation-outline" /></template>
