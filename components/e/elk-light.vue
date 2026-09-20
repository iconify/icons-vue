<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwh--inlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jwh--inlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:elk-light" /></template>
