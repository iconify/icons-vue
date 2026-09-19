<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj0ye9czm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj0ye9czm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cart-minus" /></template>
