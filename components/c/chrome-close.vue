<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-j74pbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g-j74pbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:chrome-close" /></template>
