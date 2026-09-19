<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p214o0byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="p214o0byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:image-outline" /></template>
