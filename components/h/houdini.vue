<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2hsbn8er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l2hsbn8er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:houdini" /></template>
