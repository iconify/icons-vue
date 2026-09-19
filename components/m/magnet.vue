<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx3o0m84v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mx3o0m84v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:magnet" /></template>
