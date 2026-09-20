<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2v60eklz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="s2v60eklz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-button-zigzag-both-direction-arrow-curvy-diagram-zigzag-vertical" /></template>
