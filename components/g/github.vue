<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuc69jbme.css';
import '../../css/x/x6q1qsb4x.css';
import '../../css/f/f6l_3qegk.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/d/djiglgypw.css';
import '../../css/g/g8q-87bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="nuc69jbme"/><circle class="x6q1qsb4x"/><path class="f6l_3qegk"/><g class="jn8qy4bru"><path class="djiglgypw"/><path class="g8q-87bvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:github" /></template>
