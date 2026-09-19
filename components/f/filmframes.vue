<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sttfplz3g.css';
import '../../css/e/er0fxe3xc.css';
import '../../css/c/cnwloqb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sttfplz3g"/><path class="er0fxe3xc"/><path class="cnwloqb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:filmframes" /></template>
