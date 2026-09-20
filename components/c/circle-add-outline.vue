<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9kdd-bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u9kdd-bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:circle-add-outline" /></template>
