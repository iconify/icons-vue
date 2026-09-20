<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldjj17z3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ldjj17z3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:garage-under-key" /></template>
