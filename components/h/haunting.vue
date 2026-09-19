<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q08fztv6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q08fztv6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:haunting" /></template>
