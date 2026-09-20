<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euzyw7brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euzyw7brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:blockchaindotcom" /></template>
