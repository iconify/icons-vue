<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5k1d6waj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u5k1d6waj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:flower1" /></template>
