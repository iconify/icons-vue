<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba61gnnld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ba61gnnld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:circle" /></template>
