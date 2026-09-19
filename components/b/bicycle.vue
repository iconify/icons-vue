<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csq3wgbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="csq3wgbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bicycle" /></template>
