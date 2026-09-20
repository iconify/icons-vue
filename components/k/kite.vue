<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpbjpac9g.css';
import '../../css/k/kgf0r7bvp.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/i/ihxzzib8n.css';
import '../../css/h/h9t1rz7uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="cpbjpac9g"/><path class="kgf0r7bvp"/><g class="jn8qy4bru"><path class="ihxzzib8n"/><path class="h9t1rz7uy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:kite" /></template>
