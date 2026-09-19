<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr5s_x-nn.css';
import '../../css/b/bqij9q-9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mr5s_x-nn"/><path class="bqij9q-9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:arrow-circle-left" /></template>
