<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc_22bcyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zc_22bcyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crypt-entrance" /></template>
