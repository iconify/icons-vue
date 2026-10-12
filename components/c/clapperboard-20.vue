<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf3wb_zhv.css';
import '../../css/x/xbbrjje4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nf3wb_zhv"/><path class="xbbrjje4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clapperboard-20" /></template>
