<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a808n44vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a808n44vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jekyll-light" /></template>
