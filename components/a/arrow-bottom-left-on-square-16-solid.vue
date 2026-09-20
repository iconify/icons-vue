<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0adcrzki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a0adcrzki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-bottom-left-on-square-16-solid" /></template>
