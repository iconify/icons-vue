<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5ig9cc7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":49,"height":48};
const content = `<path class="c5ig9cc7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bottom-bar-one" /></template>
