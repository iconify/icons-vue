<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrnnb9bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xrnnb9bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:branch-deleted" /></template>
