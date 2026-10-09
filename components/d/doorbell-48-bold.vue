<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_zpkg6wi.css';
import '../../css/u/uwggcevzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o_zpkg6wi"/><path class="uwggcevzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:doorbell-48-bold" /></template>
