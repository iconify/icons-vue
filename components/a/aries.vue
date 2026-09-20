<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2u1i6b4l.css';
import '../../css/h/h_pt1abna.css';
import '../../css/m/ma684bb2g.css';
import '../../css/e/e4zfowz9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="u2u1i6b4l"/><path class="h_pt1abna"/><path class="ma684bb2g"/><path class="e4zfowz9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:aries" /></template>
