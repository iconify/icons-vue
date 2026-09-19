<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc2ir_ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nc2ir_ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:folder-closed-stroke-16" /></template>
