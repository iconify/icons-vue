<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z40llcbyn.css';
import '../../css/g/g2_3tpb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z40llcbyn"/><path class="g2_3tpb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:coding-apps-websites-setting-computer" /></template>
