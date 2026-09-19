<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-62cob3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m-62cob3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:color-wand" /></template>
