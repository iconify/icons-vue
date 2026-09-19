<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd4exubgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="nd4exubgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:align-right" /></template>
