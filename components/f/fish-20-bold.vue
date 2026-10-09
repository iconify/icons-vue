<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owtzhwipg.css';
import '../../css/s/sj9o9bcjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="owtzhwipg"/><path class="sj9o9bcjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fish-20-bold" /></template>
