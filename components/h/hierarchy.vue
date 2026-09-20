<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmj8hwynf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="zmj8hwynf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:hierarchy" /></template>
