<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms-oo7b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ms-oo7b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-up-left" /></template>
