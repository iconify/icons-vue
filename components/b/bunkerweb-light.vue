<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q65z-hbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q65z-hbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bunkerweb-light" /></template>
