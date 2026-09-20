<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5ko6fbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p5ko6fbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dell" /></template>
