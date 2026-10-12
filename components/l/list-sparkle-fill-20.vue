<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk326jbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bk326jbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:list-sparkle-fill-20" /></template>
