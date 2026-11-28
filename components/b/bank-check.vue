<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eao-mibhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eao-mibhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bank-check" /></template>
