<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2vigwbeq.css';
import '../../css/j/jwwa9k2ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g2vigwbeq"/><path class="jwwa9k2ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cloud-upload" /></template>
