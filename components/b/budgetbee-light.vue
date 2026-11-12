<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eggr4hkfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eggr4hkfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:budgetbee-light" /></template>
