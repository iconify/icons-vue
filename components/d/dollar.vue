<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4psys0ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j4psys0ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dollar" /></template>
