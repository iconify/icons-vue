<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd87p4iod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fd87p4iod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cooler" /></template>
