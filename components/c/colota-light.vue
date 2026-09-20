<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2e05bcja.css';
import '../../css/j/juj0211vf.css';
import '../../css/z/zpr4ze31r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d2e05bcja"/><path class="juj0211vf"/><path class="zpr4ze31r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:colota-light" /></template>
