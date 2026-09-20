<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkt5ohbxh.css';
import '../../css/u/ukfpmsbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ouiIcon__fillSecondary xkt5ohbxh"/><path class="ukfpmsbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-gis" /></template>
