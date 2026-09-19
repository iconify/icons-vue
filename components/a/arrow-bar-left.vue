<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9_z50bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y9_z50bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-bar-left" /></template>
