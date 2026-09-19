<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntk5uyc5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ntk5uyc5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-xd" /></template>
