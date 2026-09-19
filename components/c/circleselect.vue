<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-g2blbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f-g2blbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleselect" /></template>
