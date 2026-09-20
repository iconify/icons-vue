<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww-69_hbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ww-69_hbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:crop-selection" /></template>
