<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk9p7gn2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rk9p7gn2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:flag-outline" /></template>
