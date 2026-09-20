<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-6bvg8-p.css';
import '../../css/n/naowi_jsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l-6bvg8-p"/><path class="naowi_jsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gitsave" /></template>
