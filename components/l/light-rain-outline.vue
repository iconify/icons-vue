<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwdc88brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dwdc88brc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:light-rain-outline" /></template>
