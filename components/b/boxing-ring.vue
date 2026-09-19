<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy39u9zms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sy39u9zms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:boxing-ring" /></template>
