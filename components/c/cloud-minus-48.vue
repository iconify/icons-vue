<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu424ublx.css';
import '../../css/f/f5bqv3-2b.css';
import '../../css/k/kem81wb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wu424ublx"/><path class="f5bqv3-2b"/><path class="kem81wb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-minus-48" /></template>
