<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksksr155x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ksksr155x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chevron-compact-left" /></template>
