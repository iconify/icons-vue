<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_9f3ie_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x_9f3ie_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:feather-necklace" /></template>
