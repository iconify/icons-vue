<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iku0ku7vq.css';
import '../../css/t/t1somzbtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iku0ku7vq"/><path class="t1somzbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dry-cask-20" /></template>
