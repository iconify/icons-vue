<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8l__7b2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o8l__7b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:maglev" /></template>
