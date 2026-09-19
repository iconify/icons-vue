<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arkx2sb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="arkx2sb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleup" /></template>
