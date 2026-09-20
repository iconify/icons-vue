<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i73vyxe7x.css';
import '../../css/n/nbm911b0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i73vyxe7x"/><path class="nbm911b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crow-ci-light" /></template>
