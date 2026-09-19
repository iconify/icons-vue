<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuchhbb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zuchhbb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:components" /></template>
