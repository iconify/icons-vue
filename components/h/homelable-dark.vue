<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fssu8fvgl.css';
import '../../css/k/kp6gabvbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fssu8fvgl"/><path class="kp6gabvbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homelable-dark" /></template>
