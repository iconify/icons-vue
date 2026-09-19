<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv8czdbir.css';
import '../../css/t/ti_zwx44j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xv8czdbir"/><path class="ti_zwx44j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:create" /></template>
