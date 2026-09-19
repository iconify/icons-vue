<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc6ou7bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gc6ou7bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:link-slash-16-solid" /></template>
