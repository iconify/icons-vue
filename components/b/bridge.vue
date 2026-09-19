<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up_ycpgrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="up_ycpgrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bridge" /></template>
