<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b13n3cccp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="b13n3cccp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:comment-nodes" /></template>
