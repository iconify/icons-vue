<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxnmy9bde.css';
import '../../css/m/mjttu00lo.css';
import '../../css/g/gmago3blo.css';
import '../../css/x/x-mqmdlpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bxnmy9bde"/><path class="mjttu00lo"/><path class="gmago3blo"/><path class="x-mqmdlpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:excalidash-dark" /></template>
