<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow7wuyz2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ow7wuyz2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-favorite-outline" /></template>
