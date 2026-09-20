<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5jbxh.css';
import '../../css/i/iw1iew.css';
import '../../css/r/r1zcwc.css';
import '../../css/s/so-from-28.css';
import '../../css/f/fill-to-1.css';
import '../../css/d/d-7xq8qc.css';
import '../../css/d/d-7h3jep.css';
import '../../css/f/fade-qhlvwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5jbxh iw1iew"/><path class="iw1iew r1zcwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:hazard-lights-filled-loop" /></template>
