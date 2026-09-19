<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdokhcczj.css';
import '../../css/o/ohy4x1bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pdokhcczj"/><path class="ohy4x1bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-pie" /></template>
