<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjhvz0dqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hjhvz0dqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:locust" /></template>
