<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzz1d_bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gzz1d_bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:guatemala" /></template>
