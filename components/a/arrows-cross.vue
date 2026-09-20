<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuikkvv7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xuikkvv7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:arrows-cross" /></template>
