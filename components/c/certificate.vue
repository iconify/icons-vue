<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhdbmwbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1022};
const content = `<path class="fhdbmwbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:certificate" /></template>
