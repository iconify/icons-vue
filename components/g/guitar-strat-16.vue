<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9eh8ivin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j9eh8ivin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:guitar-strat-16" /></template>
