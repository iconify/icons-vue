<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydpf4kj9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ydpf4kj9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsites" /></template>
