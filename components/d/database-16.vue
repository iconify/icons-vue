<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz7zuh0jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gz7zuh0jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:database-16" /></template>
