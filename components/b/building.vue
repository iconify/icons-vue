<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u__b9iwlh.css';
import '../../css/w/wqtak9bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u__b9iwlh"/><path class="wqtak9bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:building" /></template>
