<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmrl7o3_k.css';
import '../../css/c/clim-4j3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="fmrl7o3_k"/><path class="clim-4j3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-body" /></template>
