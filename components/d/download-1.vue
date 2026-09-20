<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znkyzi2mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="znkyzi2mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:download-1" /></template>
