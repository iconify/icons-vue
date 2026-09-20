<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcjf6bcsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcjf6bcsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:bullet-square" /></template>
