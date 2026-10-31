<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dky4xzbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dky4xzbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-box-gabled-building-with-door" /></template>
