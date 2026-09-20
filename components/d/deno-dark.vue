<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evnwlobir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":441,"height":441};
const content = `<path class="evnwlobir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:deno-dark" /></template>
