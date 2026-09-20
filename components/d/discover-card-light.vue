<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0yozqbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t0yozqbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:discover-card-light" /></template>
