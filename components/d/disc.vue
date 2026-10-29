<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/far50iw7l.css';
import '../../css/f/fs0yrab0m.css';
import '../../css/h/hffkpbehn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="far50iw7l wm-k"/><path class="fs0yrab0m wm-a"/><path class="hffkpbehn wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:disc" /></template>
