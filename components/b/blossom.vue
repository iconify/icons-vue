<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-4szbwhd.css';
import '../../css/x/x878rrbin.css';
import '../../css/h/hoyfu1b9w.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/s/s7zo5sbdd.css';
import '../../css/w/wy5fk2b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="g-4szbwhd"/><path class="x878rrbin"/><path class="hoyfu1b9w"/><g class="jn8qy4bru"><circle class="s7zo5sbdd"/><path class="wy5fk2b1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:blossom" /></template>
