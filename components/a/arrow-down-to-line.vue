<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxr-nkffo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xxr-nkffo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-down-to-line" /></template>
