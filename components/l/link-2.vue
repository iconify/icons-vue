<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckg-0r-5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ckg-0r-5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:link-2" /></template>
