<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi_9_0blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zi_9_0blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:d-arrow-left" /></template>
