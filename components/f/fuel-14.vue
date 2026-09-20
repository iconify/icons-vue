<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2wv2hb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="s2wv2hb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:fuel-14" /></template>
