<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/che1mymjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="che1mymjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-left" /></template>
