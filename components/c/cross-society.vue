<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jddr2hbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jddr2hbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cross-society" /></template>
