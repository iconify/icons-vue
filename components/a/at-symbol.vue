<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct1ofye1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="ct1ofye1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:at-symbol" /></template>
