<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht2xmabmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ht2xmabmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lips" /></template>
