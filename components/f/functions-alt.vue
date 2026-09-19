<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc1e6ys7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fc1e6ys7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:functions-alt" /></template>
