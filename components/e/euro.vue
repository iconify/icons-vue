<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnd7fwbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gnd7fwbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:euro" /></template>
