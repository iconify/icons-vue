<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x16rdgb4k.css';
import '../../css/s/s_9jp5bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x16rdgb4k"/><path class="s_9jp5bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-locked" /></template>
