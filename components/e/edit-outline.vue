<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7npx6d9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y7npx6d9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:edit-outline" /></template>
