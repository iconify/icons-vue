<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9qhx1bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r9qhx1bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:conical-flask" /></template>
