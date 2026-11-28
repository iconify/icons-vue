<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f22cp5rgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f22cp5rgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:dna-check" /></template>
