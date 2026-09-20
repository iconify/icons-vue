<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihurembfg.css';
import '../../css/d/doj9dq_jg.css';
import '../../css/b/bepahm04n.css';
import '../../css/j/jimrxwnfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ihurembfg"/><g class="doj9dq_jg"><path class="bepahm04n"/><path class="jimrxwnfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:cloud-with-snow" /></template>
