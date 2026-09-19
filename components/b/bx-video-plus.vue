<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx1df9t7l.css';
import '../../css/c/cjnhv0ssg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx1df9t7l"/><path class="cjnhv0ssg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-video-plus" /></template>
