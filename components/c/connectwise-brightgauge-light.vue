<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9mwpfk9f.css';
import '../../css/p/phkuhv_dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o9mwpfk9f"/><path class="phkuhv_dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:connectwise-brightgauge-light" /></template>
