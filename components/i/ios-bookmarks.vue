<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4zgz8bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y4zgz8bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-bookmarks" /></template>
