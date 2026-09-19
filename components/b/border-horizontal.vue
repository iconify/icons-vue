<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exl30abif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="exl30abif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:border-horizontal" /></template>
