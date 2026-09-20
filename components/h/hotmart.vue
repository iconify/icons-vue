<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0-v6c_3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":37};
const content = `<path class="m0-v6c_3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hotmart" /></template>
