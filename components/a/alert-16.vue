<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhhy9kbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nhhy9kbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:alert-16" /></template>
