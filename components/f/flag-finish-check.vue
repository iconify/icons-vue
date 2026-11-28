<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj0wbccem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj0wbccem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:flag-finish-check" /></template>
