<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv6_n6e5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uv6_n6e5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:big-wave" /></template>
