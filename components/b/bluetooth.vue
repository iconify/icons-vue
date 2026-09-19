<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivgi5xbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1026};
const content = `<path class="ivgi5xbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bluetooth" /></template>
