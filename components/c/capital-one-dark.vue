<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thiduhgzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="thiduhgzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:capital-one-dark" /></template>
