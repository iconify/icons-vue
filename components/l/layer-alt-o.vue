<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6oibxtkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="d6oibxtkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-alt-o" /></template>
