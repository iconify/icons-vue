<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5n5_gptj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s5n5_gptj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-arrow-path-16-solid" /></template>
