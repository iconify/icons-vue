<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb-8z_bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qb-8z_bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:droplet-fill" /></template>
