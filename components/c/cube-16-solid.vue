<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivj7y7blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ivj7y7blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cube-16-solid" /></template>
