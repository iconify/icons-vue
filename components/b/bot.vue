<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1tr5shfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o1tr5shfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:bot" /></template>
