<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/w69n2x5jx.css';
import '../../css/i/i378c-rig.css';
import '../../css/k/k8okabcwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="w69n2x5jx"/><path class="i378c-rig wm-a"/><path class="k8okabcwj wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:calendar-search-solid" /></template>
