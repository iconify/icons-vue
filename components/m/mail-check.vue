<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/l05kllblb.css';
import '../../css/m/mvuk3sn6m.css';
import '../../css/t/te-uyzerb.css';
import '../../css/s/s07l5sb7t.css';
import '../../css/o/o9p1zzt3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="l05kllblb wm-shadow"/><path class="mvuk3sn6m wm-shadow"/><path class="te-uyzerb"/><path class="s07l5sb7t"/><path class="o9p1zzt3p wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:mail-check" /></template>
