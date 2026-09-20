<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0w2mtbgl.css';
import '../../css/t/tl1zu4bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e0w2mtbgl"/><path class="tl1zu4bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:briefing" /></template>
