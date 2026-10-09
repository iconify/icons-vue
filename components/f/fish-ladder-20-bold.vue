<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7q9v--5u.css';
import '../../css/u/uefc_6bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n7q9v--5u"/><path class="uefc_6bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fish-ladder-20-bold" /></template>
