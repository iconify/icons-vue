<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_9jp5bhq.css';
import '../../css/y/yszbrkbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s_9jp5bhq"/><path class="yszbrkbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-unlocked" /></template>
