<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rku15hbsi.css';
import '../../css/k/k3idjubot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rku15hbsi"/><path class="k3idjubot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flow-like" /></template>
