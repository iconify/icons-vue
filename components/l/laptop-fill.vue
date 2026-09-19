<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pscki0bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pscki0bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:laptop-fill" /></template>
