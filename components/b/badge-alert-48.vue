<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jha4hptgn.css';
import '../../css/u/uq6wzpn-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jha4hptgn"/><path class="uq6wzpn-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:badge-alert-48" /></template>
