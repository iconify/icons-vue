<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv-wqkbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lv-wqkbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bluesky-light" /></template>
