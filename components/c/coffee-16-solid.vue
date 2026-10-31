<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0f5hxbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a0f5hxbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:coffee-16-solid" /></template>
