<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3cs2pb3j.css';
import '../../css/s/siyl6_4rk.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/e/eg2oelb-s.css';
import '../../css/w/wu-qhsb3w.css';
import '../../css/w/wqis7mbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<ellipse transform="rotate(-70 36 30.5)" class="o3cs2pb3j"/><path class="siyl6_4rk"/><g class="jn8qy4bru"><ellipse transform="rotate(-69.796 36 30.5)" class="eg2oelb-s"/><ellipse transform="rotate(-70 36 30.5)" class="wu-qhsb3w"/><path class="wqis7mbhr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flying-disc" /></template>
