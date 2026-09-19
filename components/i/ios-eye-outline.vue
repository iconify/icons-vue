<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4ba3tqnk.css';
import '../../css/z/z5kklv8jo.css';
import '../../css/a/agjlaub_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u4ba3tqnk"/><path class="z5kklv8jo"/><path class="agjlaub_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-eye-outline" /></template>
