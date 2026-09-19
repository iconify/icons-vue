<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c57rmubuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c57rmubuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:basketball" /></template>
