<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-_pmti1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a-_pmti1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:geo" /></template>
