<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p03_kqbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p03_kqbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:contract-across-outline" /></template>
