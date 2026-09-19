<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysqdi1b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ysqdi1b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bat-mask" /></template>
