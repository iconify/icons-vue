<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkgq6cbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mkgq6cbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:list-unordered" /></template>
