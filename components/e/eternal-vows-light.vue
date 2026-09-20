<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm4zn8bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wm4zn8bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eternal-vows-light" /></template>
