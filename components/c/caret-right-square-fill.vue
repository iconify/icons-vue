<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtrg6izee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vtrg6izee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:caret-right-square-fill" /></template>
