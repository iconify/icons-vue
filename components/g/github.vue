<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vog0rrf_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vog0rrf_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:github" /></template>
