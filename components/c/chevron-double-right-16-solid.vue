<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0ri7lbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e0ri7lbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-double-right-16-solid" /></template>
