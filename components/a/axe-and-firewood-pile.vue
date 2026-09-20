<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk6i8-bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rk6i8-bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:axe-and-firewood-pile" /></template>
