<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb_3d7atl.css';
import '../../css/m/mtfesl_yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mb_3d7atl"/><path class="mtfesl_yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-mic" /></template>
