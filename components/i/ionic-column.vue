<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znorxjctx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="znorxjctx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ionic-column" /></template>
