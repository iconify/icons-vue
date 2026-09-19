<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq4yvfb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="yq4yvfb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:chevron-circle-up" /></template>
