<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adblgzbva.css';
import '../../css/y/ybwzvccuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="adblgzbva"/><path class="ybwzvccuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-redo-circle-outline" /></template>
