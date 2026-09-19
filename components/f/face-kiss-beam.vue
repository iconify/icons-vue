<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luzm4jb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="luzm4jb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-kiss-beam" /></template>
