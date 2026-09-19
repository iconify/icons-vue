<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb34d8b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="pb34d8b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:long-arrow-alt-down" /></template>
