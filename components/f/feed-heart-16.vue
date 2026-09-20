<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajunkfbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ajunkfbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-heart-16" /></template>
