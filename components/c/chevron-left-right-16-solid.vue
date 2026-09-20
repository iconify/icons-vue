<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2lbzywut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o2lbzywut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chevron-left-right-16-solid" /></template>
