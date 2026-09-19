<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q00_snggc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q00_snggc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:arrow-left" /></template>
