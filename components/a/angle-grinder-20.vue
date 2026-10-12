<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao-tyjbir.css';
import '../../css/r/rtr7zsbdu.css';
import '../../css/d/don67qb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ao-tyjbir"/><path class="rtr7zsbdu"/><path class="don67qb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:angle-grinder-20" /></template>
