<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzfeitich.css';
import '../../css/j/jzxguacfp.css';
import '../../css/v/v8s6amb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="qzfeitich"/><path class="jzxguacfp"/><path class="v8s6amb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:elevator" /></template>
