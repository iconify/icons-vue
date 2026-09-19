<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph1egc8-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ph1egc8-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:bucket-fill" /></template>
