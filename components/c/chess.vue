<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uty3owbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="uty3owbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:chess" /></template>
