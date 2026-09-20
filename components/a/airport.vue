<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1kipxb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="u1kipxb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:airport" /></template>
