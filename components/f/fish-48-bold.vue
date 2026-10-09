<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-1_twbuv.css';
import '../../css/u/un8javbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d-1_twbuv"/><path class="un8javbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fish-48-bold" /></template>
