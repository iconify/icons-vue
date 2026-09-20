<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-1x-c_ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x-1x-c_ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-switch-16" /></template>
