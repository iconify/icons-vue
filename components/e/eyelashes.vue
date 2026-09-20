<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_h617p5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q_h617p5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eyelashes" /></template>
