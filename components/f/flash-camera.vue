<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xob65pb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xob65pb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flash-camera" /></template>
