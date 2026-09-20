<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb2sq0b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jb2sq0b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbterm-dark" /></template>
