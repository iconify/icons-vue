<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozby7f9jz.css';
import '../../css/p/px_2rvbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ozby7f9jz"/><path class="px_2rvbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:hourglass-outline" /></template>
