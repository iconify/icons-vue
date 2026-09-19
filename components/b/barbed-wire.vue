<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zql7dlb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zql7dlb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:barbed-wire" /></template>
