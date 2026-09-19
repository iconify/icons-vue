<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u901n4bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u901n4bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:designer-news" /></template>
