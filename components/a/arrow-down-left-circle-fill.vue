<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr7h7gujd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gr7h7gujd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-down-left-circle-fill" /></template>
