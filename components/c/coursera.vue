<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl3b5mb1m.css';
import '../../css/e/evze903ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="rl3b5mb1m"/><path class="evze903ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:coursera" /></template>
