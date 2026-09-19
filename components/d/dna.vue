<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv40akbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv40akbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:dna" /></template>
