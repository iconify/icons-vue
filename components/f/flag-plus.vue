<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m59tlb5eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m59tlb5eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:flag-plus" /></template>
