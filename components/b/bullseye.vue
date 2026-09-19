<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo5bo8b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xo5bo8b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bullseye" /></template>
