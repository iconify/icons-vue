<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhkjd6b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mhkjd6b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arc-third-16-solid" /></template>
