<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkvyz5baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tkvyz5baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:glasses" /></template>
