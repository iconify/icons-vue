<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxt3-pber.css';
import '../../css/k/k18y-k1ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxt3-pber"/><path class="k18y-k1ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:airport-sign-1" /></template>
