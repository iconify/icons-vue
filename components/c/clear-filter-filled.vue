<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6ovz8bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="y6ovz8bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:clear-filter-filled" /></template>
