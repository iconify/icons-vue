<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybue2s69d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ybue2s69d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:face-frown" /></template>
