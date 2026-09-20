<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8e4yyaeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b8e4yyaeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:download-4" /></template>
