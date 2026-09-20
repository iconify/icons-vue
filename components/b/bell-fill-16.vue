<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni8m26bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ni8m26bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bell-fill-16" /></template>
