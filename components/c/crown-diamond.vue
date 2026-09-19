<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-ji6ybfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p-ji6ybfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:crown-diamond" /></template>
