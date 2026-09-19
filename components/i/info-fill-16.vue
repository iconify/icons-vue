<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-ccc-byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v-ccc-byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:info-fill-16" /></template>
