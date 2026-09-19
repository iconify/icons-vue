<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0mitemhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d0mitemhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:football" /></template>
