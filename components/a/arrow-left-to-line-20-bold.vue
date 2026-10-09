<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emvwi1bcs.css';
import '../../css/f/f-3_hbcnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="emvwi1bcs"/><path class="f-3_hbcnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-left-to-line-20-bold" /></template>
