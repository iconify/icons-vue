<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aghwx5bsq.css';
import '../../css/t/tel8tmb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aghwx5bsq"/><path class="tel8tmb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:link-20-bold" /></template>
