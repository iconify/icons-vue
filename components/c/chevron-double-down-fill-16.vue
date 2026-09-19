<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1m6q9zqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p1m6q9zqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-double-down-fill-16" /></template>
