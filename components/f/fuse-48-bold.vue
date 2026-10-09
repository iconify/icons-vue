<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfno_j3ae.css';
import '../../css/w/w-p1obhec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sfno_j3ae"/><path class="w-p1obhec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuse-48-bold" /></template>
