<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf0zdtb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="kf0zdtb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:dna" /></template>
