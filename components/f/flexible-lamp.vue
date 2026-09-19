<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4r-5wgdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h4r-5wgdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flexible-lamp" /></template>
