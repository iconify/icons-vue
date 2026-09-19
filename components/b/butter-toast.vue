<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu328sq7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zu328sq7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:butter-toast" /></template>
