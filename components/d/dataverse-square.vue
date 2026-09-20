<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cujrrqbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="cujrrqbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:dataverse-square" /></template>
