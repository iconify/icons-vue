<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1z-bmbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c1z-bmbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:ban-fill" /></template>
