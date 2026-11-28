<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2lnp2nzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2lnp2nzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:calculator-check" /></template>
