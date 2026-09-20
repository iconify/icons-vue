<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3ubpnbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y3ubpnbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:command-flat" /></template>
