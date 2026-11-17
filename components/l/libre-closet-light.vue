<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1yubo85f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h1yubo85f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:libre-closet-light" /></template>
