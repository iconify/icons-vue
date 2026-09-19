<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mchuo9ucv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mchuo9ucv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:android2" /></template>
