<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgi-m3bfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jgi-m3bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:align-text-left" /></template>
