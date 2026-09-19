<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rulit7brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rulit7brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:home-alt-slim-horiz" /></template>
