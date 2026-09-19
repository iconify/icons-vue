<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thv_lrbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thv_lrbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:chapel" /></template>
