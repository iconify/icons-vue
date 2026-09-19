<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m74_d7bth.css';
import '../../css/k/ky4ks4bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m74_d7bth"/><path class="ky4ks4bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:filter-square" /></template>
