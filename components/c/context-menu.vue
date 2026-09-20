<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guicaeb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="guicaeb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:context-menu" /></template>
