<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt2xskbcf.css';
import '../../css/q/q-tflgzje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yt2xskbcf"/><path class="q-tflgzje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:arrow-down-circle-outline" /></template>
