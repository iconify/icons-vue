<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw-0snbeq.css';
import '../../css/z/zxh8vllwu.css';
import '../../css/t/tfwvdwbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fw-0snbeq"/><path class="ouiIcon__fillSecondary zxh8vllwu"/><path class="tfwvdwbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-console" /></template>
