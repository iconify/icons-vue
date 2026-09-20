<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-mfvhccf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v-mfvhccf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:arrow-left" /></template>
