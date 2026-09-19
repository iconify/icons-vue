<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgykehbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dgykehbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:headset-sparkle-fill-12" /></template>
