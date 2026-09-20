<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk5b0uhxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gk5b0uhxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:card-and-dice" /></template>
