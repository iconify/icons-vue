<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj7xkoehg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dj7xkoehg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:flag" /></template>
