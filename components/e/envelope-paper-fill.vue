<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y14p00b7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y14p00b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:envelope-paper-fill" /></template>
