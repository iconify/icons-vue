<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez09jybdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ez09jybdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:javascript-outline" /></template>
