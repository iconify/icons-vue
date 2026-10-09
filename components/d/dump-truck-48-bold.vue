<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axlm26blc.css';
import '../../css/t/taruh-bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="axlm26blc"/><path class="taruh-bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dump-truck-48-bold" /></template>
