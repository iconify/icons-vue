<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjlwf8m8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vjlwf8m8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-long-down-16-solid" /></template>
