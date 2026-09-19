<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmw875old.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zmw875old"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chevron-right" /></template>
