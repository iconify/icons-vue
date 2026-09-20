<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in4ij8bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="in4ij8bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:h5-16-solid" /></template>
