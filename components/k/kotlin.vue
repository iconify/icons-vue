<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9di_s0jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="l9di_s0jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:kotlin" /></template>
