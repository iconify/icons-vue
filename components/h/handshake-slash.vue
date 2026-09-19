<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f65yucmlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="f65yucmlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:handshake-slash" /></template>
