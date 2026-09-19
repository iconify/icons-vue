<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn1xveb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sn1xveb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrows-expand-vertical" /></template>
