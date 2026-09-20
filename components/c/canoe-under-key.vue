<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/who-i1bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="who-i1bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:canoe-under-key" /></template>
