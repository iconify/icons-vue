<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy2r1xdnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sy2r1xdnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jawbone" /></template>
