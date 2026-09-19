<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfdxk_9-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vfdxk_9-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:imprisoned" /></template>
