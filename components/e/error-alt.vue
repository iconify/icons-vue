<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0pnj58ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="u0pnj58ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:error-alt" /></template>
