<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwl9mh0ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bwl9mh0ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-right-arrow-left" /></template>
