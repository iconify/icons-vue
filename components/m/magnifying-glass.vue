<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9ohq6b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n9ohq6b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:magnifying-glass" /></template>
