<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je9p0tb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="je9p0tb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:hourglass" /></template>
