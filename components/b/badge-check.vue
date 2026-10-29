<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqdsmob1w.css';
import '../../css/a/a5q1z5qkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqdsmob1w wm-k"/><path class="a5q1z5qkn wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:badge-check" /></template>
