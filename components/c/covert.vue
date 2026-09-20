<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/b/bwxu_9b1w.css';
import '../../css/a/aspvo2b2l.css';
import '../../css/s/s2kk1gb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bwxu_9b1w"/><path class="aspvo2b2l"/><path class="s2kk1gb9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:covert" /></template>
