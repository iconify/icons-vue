<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8id8bbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y8id8bbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:compass-16-solid" /></template>
