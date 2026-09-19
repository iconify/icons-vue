<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiofm1w_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiofm1w_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:between-horizontal-end" /></template>
