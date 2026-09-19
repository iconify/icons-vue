<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rptdwfb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rptdwfb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:book" /></template>
