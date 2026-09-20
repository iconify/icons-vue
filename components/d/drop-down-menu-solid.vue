<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo5m2nblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yo5m2nblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:drop-down-menu-solid" /></template>
