<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3bz6eb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c3bz6eb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:folder" /></template>
