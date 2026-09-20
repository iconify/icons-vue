<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y135jsbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y135jsbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cc-text" /></template>
