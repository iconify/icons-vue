<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcu0spkpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="dcu0spkpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:circle-grid-3x3-fill" /></template>
