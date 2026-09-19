<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfp7kbbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pfp7kbbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bookmark-square-16-solid" /></template>
