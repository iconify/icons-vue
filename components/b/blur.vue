<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz94q6zst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qz94q6zst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:blur" /></template>
