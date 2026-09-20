<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bphhl4wef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="bphhl4wef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:kayaking" /></template>
