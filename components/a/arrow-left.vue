<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebldvkbho.css';
import '../../css/q/q_3cglb4g.css';
import '../../css/d/dxxog678i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ebldvkbho"/><path class="q_3cglb4g"/><path class="dxxog678i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:arrow-left" /></template>
