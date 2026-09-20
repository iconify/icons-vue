<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmxhs-b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="nmxhs-b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:computer-virtual-reality-gaming-virtual-gear-controller-reality-games-headset-technology-vr-eyewear" /></template>
