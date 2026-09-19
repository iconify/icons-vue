<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6a4ylago.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="s6a4ylago"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:comment-more" /></template>
