<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqlg3vbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iqlg3vbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:fast-backward" /></template>
