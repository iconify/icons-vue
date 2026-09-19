<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s75iopu5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s75iopu5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-bookmarks-outline" /></template>
