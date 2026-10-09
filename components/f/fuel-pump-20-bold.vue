<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azc5oubyv.css';
import '../../css/y/ywfl4rbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="azc5oubyv"/><path class="ywfl4rbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuel-pump-20-bold" /></template>
