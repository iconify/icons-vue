<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wu-rm0sbq.css';
import '../../css/b/bcnfd8ber.css';
import '../../css/y/ysf3pfyth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="wu-rm0sbq"/><path class="bcnfd8ber"/><path class="ysf3pfyth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:dolphin" /></template>
