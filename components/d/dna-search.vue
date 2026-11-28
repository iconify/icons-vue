<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln_o54bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln_o54bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:dna-search" /></template>
