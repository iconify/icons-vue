<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq6c9lvbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mq6c9lvbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ice-cube" /></template>
