<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m769hdc0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m769hdc0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-earmark-x-fill" /></template>
