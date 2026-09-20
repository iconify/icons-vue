<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh32qp8wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wh32qp8wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:information" /></template>
