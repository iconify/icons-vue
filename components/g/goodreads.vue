<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb5n4phcw.css';
import '../../css/d/dggo-4bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yb5n4phcw"/><path class="dggo-4bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:goodreads" /></template>
