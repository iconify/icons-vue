<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp_ciybgk.css';
import '../../css/k/k-_lh2bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mp_ciybgk"/><path class="k-_lh2bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:database-fill-20" /></template>
