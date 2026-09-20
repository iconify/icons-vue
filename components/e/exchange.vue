<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3q8gnbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h3q8gnbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:exchange" /></template>
