<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4ytt9oqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a4ytt9oqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-double-left-16-solid" /></template>
