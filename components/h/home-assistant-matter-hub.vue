<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpif0vp-i.css';
import '../../css/v/vd05wq3fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jpif0vp-i"/><path class="vd05wq3fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:home-assistant-matter-hub" /></template>
