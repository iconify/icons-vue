<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1-g0ub6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u1-g0ub6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:hoplon" /></template>
