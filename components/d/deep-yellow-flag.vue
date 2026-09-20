<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dur0b2p3t.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="dur0b2p3t"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:deep-yellow-flag" /></template>
