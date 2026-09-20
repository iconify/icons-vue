<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5ydwh_7g.css';
import '../../css/m/mgkytmtsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u5ydwh_7g"/><path class="mgkytmtsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:anchor-top-middle-16" /></template>
