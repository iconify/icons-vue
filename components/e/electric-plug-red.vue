<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifigabb1m.css';
import '../../css/j/j_hu1tb8r.css';
import '../../css/h/hp8eoxorl.css';
import '../../css/z/z04drlb1l.css';
import '../../css/l/lp2ifebua.css';
import '../../css/e/eygst5bhk.css';
import '../../css/j/j84d5ebto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ifigabb1m"/><path class="j_hu1tb8r"/><path class="hp8eoxorl"/><g class="z04drlb1l"><path class="lp2ifebua"/><path class="eygst5bhk"/><path class="j84d5ebto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:electric-plug-red" /></template>
