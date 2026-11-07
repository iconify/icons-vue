<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zscshfblg.css';
import '../../css/f/fpavm-beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zscshfblg"/><path class="fpavm-beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chef-hat-minimalistic-bold-duotone" /></template>
