<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oen2_6b7t.css';
import '../../css/n/nv21e7b0y.css';
import '../../css/a/ao36abnej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="oen2_6b7t"/><circle class="nv21e7b0y"/><path class="ao36abnej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:forkknife" /></template>
