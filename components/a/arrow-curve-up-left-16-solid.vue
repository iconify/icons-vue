<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-1lzjfhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g-1lzjfhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-up-left-16-solid" /></template>
