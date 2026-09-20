<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3u-g3b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g3u-g3b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:iterations-16" /></template>
