<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/firpjtj6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="firpjtj6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:interlocking-rings-fill-16" /></template>
