<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xme-khm4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="xme-khm4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bullhorn" /></template>
