<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hxkoqb07q.css';
import '../../css/g/go4d8z99l.css';
import '../../css/w/weboadcul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="cuyn6tgcc"><path class="hxkoqb07q"/><path class="go4d8z99l"/><path class="weboadcul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:jasmine-wordmark" /></template>
