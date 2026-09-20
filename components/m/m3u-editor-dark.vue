<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl88n_b7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rl88n_b7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:m3u-editor-dark" /></template>
