<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe5_628xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fe5_628xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-earmark-fill" /></template>
