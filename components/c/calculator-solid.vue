<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l03st-bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="l03st-bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:calculator-solid" /></template>
