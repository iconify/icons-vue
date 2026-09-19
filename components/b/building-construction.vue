<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx33p9m0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="tx33p9m0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:building-construction" /></template>
