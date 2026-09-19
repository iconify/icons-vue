<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7ys7fbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l7ys7fbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:align-right" /></template>
