<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4l8cxbpg.css';
import '../../css/j/j6agt1nji.css';
import '../../css/x/x07i0sb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t4l8cxbpg"/><path class="j6agt1nji"/><path class="x07i0sb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cassette-20" /></template>
