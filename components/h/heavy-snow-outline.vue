<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzxn7xbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bzxn7xbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:heavy-snow-outline" /></template>
