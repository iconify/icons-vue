<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i48ixpics.css';
import '../../css/q/q0dd0fvak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i48ixpics"/><path class="q0dd0fvak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dosvault-dark" /></template>
