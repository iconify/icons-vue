<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx0wpfbrz.css';
import '../../css/y/yc_qcr2ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gx0wpfbrz"/><path class="yc_qcr2ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:contract-20-bold" /></template>
