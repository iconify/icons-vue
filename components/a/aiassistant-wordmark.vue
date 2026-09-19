<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkn_koeov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dkn_koeov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:aiassistant-wordmark" /></template>
