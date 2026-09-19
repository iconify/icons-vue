<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqu-xr9bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="jqu-xr9bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:frown-o" /></template>
