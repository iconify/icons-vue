<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8ol-ejya.css';
import '../../css/y/ykuarwblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y8ol-ejya"/><path class="ykuarwblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-time" /></template>
