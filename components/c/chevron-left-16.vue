<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrayo7mvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wrayo7mvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chevron-left-16" /></template>
