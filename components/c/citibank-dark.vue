<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj3p5qbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kj3p5qbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:citibank-dark" /></template>
