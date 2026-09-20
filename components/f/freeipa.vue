<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3zbv3b1e.css';
import '../../css/z/zu9lzmbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v3zbv3b1e"/><path class="zu9lzmbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freeipa" /></template>
