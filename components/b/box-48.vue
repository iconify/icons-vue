<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8_bhcc6x.css';
import '../../css/i/i0wzpzqff.css';
import '../../css/x/x3jtncb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v8_bhcc6x"/><path class="i0wzpzqff"/><path class="x3jtncb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:box-48" /></template>
