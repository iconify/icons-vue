<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1rz05bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s1rz05bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:free" /></template>
