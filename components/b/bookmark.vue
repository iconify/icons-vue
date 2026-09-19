<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6j73nbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="o6j73nbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:bookmark" /></template>
