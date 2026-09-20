<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eygexwqbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="eygexwqbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:gsm2" /></template>
