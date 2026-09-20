<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgsqbac3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fgsqbac3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-with-ruble" /></template>
