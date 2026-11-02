<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/til_8xb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="til_8xb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-left-down-16-solid" /></template>
