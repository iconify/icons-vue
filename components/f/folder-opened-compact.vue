<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf57mkbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kf57mkbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:folder-opened-compact" /></template>
