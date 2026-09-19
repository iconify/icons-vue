<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrb1y4wkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrb1y4wkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-sub-right-down" /></template>
