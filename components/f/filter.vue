<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu6lcp3xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tu6lcp3xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:filter" /></template>
