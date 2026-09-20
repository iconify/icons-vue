<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjm2aabla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="pjm2aabla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bedbunk" /></template>
