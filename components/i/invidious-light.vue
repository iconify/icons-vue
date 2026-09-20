<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8543qbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r8543qbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invidious-light" /></template>
