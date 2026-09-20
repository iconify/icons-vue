<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1kzdpb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n1kzdpb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:comment-dollar-solid" /></template>
