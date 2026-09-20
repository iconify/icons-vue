<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezmn_4spe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ezmn_4spe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:calculator-outline" /></template>
