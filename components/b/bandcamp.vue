<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9p9bs7fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="x9p9bs7fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bandcamp" /></template>
