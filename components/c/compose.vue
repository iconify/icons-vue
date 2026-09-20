<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxw2sxb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qxw2sxb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:compose" /></template>
