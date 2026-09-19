<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_vq-abkk.css';
import '../../css/i/i83sn7bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i_vq-abkk"/><path class="i83sn7bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:high-priority" /></template>
