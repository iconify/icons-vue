<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9zz_l4jl.css';
import '../../css/m/m8f41sb6p.css';
import '../../css/c/cnvsi8cop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y9zz_l4jl"/><path class="m8f41sb6p"/><path class="cnvsi8cop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dna-48-bold" /></template>
