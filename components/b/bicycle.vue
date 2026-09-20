<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye30ufs3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ye30ufs3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bicycle" /></template>
