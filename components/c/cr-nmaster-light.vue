<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poddgvb-j.css';
import '../../css/u/uqp1_ibtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="poddgvb-j"/><path class="uqp1_ibtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cr-nmaster-light" /></template>
