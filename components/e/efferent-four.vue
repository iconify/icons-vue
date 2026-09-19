<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grf5u8f1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="grf5u8f1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:efferent-four" /></template>
