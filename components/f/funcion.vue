<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0cbrxbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t0cbrxbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:funcion" /></template>
