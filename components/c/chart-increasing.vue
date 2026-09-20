<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi9mmib_a.css';
import '../../css/l/lji3cgbti.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/k/kxjot_1jc.css';
import '../../css/a/ab8m_jbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zi9mmib_a"/><path class="lji3cgbti"/><g class="ij2x_72vy"><path class="kxjot_1jc"/><path class="ab8m_jbxj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:chart-increasing" /></template>
