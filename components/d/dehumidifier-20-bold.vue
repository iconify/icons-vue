<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp_3l1bkn.css';
import '../../css/k/kyukd-byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fp_3l1bkn"/><path class="kyukd-byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dehumidifier-20-bold" /></template>
