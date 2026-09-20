<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6ctxebdq.css';
import '../../css/z/zyi-hacts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j6ctxebdq"/><path class="zyi-hacts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:imdb" /></template>
