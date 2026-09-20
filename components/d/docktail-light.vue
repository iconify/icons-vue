<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex6wzyber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ex6wzyber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docktail-light" /></template>
