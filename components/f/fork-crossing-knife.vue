<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuq106bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nuq106bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fork-crossing-knife" /></template>
