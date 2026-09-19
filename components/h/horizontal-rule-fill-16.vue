<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlvzh0b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xlvzh0b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:horizontal-rule-fill-16" /></template>
