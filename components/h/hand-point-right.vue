<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0cihnbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h0cihnbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hand-point-right" /></template>
