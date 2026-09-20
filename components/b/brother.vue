<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl30djqpt.css';
import '../../css/a/ad8qs5b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rl30djqpt"/><path class="ad8qs5b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:brother" /></template>
