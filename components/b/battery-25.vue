<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc2n7monf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yc2n7monf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:battery-25" /></template>
