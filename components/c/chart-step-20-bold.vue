<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w01dflzvf.css';
import '../../css/k/kmv2i6xfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w01dflzvf"/><path class="kmv2i6xfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-step-20-bold" /></template>
