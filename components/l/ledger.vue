<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnbe30brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":383,"height":128};
const content = `<path class="vnbe30brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ledger" /></template>
