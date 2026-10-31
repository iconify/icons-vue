<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpe4y4bdd.css';
import '../../css/a/a0m2q3bsg.css';
import '../../css/f/fqhq6fbgo.css';
import '../../css/e/edfqzq-tl.css';
import '../../css/s/ss0x5acba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<g display="block"><path class="mpe4y4bdd"/><path class="a0m2q3bsg"/><path class="fqhq6fbgo"/><path class="edfqzq-tl"/><path class="ss0x5acba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:dumpling" /></template>
