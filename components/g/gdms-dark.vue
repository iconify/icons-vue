<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywys17btk.css';
import '../../css/j/j4njxhbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ywys17btk"/><path class="j4njxhbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gdms-dark" /></template>
