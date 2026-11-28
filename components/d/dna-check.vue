<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmt6w7bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmt6w7bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:dna-check" /></template>
