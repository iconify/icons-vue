<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcznrtbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xcznrtbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:4-circle-fill" /></template>
