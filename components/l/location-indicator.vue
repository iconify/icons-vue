<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p51xy1bjv.css';
import '../../css/l/l9f-ppx6t.css';
import '../../css/d/de4zi-rmb.css';
import '../../css/r/r96a52_mw.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/e/ez1tzd18z.css';
import '../../css/o/o9d6gvbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="p51xy1bjv"/><path class="l9f-ppx6t"/><path class="de4zi-rmb"/><path class="r96a52_mw"/><g class="jn8qy4bru"><circle class="ez1tzd18z"/><path class="o9d6gvbai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:location-indicator" /></template>
