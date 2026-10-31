<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8r1fcc5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8r1fcc5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-search-gloss" /></template>
