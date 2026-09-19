<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au37i9bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="au37i9bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:align-center" /></template>
