<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhjgerw1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nhjgerw1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:crossing-markings-surface" /></template>
