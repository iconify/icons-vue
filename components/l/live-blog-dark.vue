<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fui6c76in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fui6c76in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:live-blog-dark" /></template>
