<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2ln8hpzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d2ln8hpzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:compass-16-solid" /></template>
