<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnyvk34hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gnyvk34hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-down-circle-16-solid" /></template>
