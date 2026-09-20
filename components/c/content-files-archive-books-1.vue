<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjxlhlb8t.css';
import '../../css/s/sv5erwbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qjxlhlb8t"/><path class="sv5erwbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:content-files-archive-books-1" /></template>
