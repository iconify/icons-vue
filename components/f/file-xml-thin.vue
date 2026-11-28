<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2dwiwbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c2dwiwbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-xml-thin" /></template>
