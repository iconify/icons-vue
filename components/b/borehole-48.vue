<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmv_a2yqj.css';
import '../../css/c/cobs7vbil.css';
import '../../css/v/vqlps0jzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lmv_a2yqj"/><path class="cobs7vbil"/><path class="vqlps0jzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:borehole-48" /></template>
