<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/r/rwd8asbpl.css';
import '../../css/q/q-2jfmgll.css';
import '../../css/i/ihmczr5tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="rwd8asbpl"/><path class="q-2jfmgll"/><path class="ihmczr5tw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:access-context-manager" /></template>
