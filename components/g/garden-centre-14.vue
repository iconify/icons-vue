<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwt559b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="iwt559b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:garden-centre-14" /></template>
