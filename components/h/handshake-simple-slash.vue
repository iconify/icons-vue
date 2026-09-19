<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9_4cub3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="d9_4cub3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:handshake-simple-slash" /></template>
