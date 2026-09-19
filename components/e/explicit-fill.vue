<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blt9k2ogm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="blt9k2ogm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:explicit-fill" /></template>
