<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5hs5qbej.css';
import '../../css/x/xl_i265-u.css';
import '../../css/d/d42sx8bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":16};
const content = `<path class="z5hs5qbej"/><path class="xl_i265-u"/><path class="d42sx8bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:books" /></template>
