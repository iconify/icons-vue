<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-bf3xbdx.css';
import '../../css/z/zmolltb3u.css';
import '../../css/a/a_mixmbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="z-bf3xbdx"/><path class="zmolltb3u"/><path class="a_mixmbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:es-pv-4x3" /></template>
