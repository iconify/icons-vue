<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7h13bb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e7h13bb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:chevrons-up" /></template>
