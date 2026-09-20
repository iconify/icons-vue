<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs4-vbmfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xs4-vbmfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coral" /></template>
