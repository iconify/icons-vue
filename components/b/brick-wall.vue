<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6rx894qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n6rx894qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:brick-wall" /></template>
