<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_raf5bng.css';
import '../../css/j/jyzrcrb7b.css';
import '../../css/q/qqexecxho.css';
import '../../css/t/t3fkntbgu.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/p/p0hl-pd-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="e_raf5bng"><ellipse class="jyzrcrb7b"/><ellipse class="qqexecxho"/><ellipse class="t3fkntbgu"/></g><g class="jn8qy4bru"><path class="p0hl-pd-h"/><ellipse class="jyzrcrb7b"/><ellipse class="qqexecxho"/><ellipse class="t3fkntbgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:ant" /></template>
