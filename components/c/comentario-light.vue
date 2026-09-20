<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9y1xtn3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l9y1xtn3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:comentario-light" /></template>
