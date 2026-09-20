<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7zh4ybar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f7zh4ybar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:check-circle-16" /></template>
