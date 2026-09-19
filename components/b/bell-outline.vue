<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2dqbpl9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="g2dqbpl9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bell-outline" /></template>
