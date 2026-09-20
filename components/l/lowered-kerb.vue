<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edo1bac0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="edo1bac0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:lowered-kerb" /></template>
