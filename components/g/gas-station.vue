<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_a8v-fgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":384};
const content = `<path class="h_a8v-fgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:gas-station" /></template>
