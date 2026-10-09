<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb2mawalq.css';
import '../../css/v/vzv6lusvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eb2mawalq"/><path class="vzv6lusvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-bottle-48-bold" /></template>
