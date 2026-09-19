<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng_wumbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ng_wumbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dark-squad" /></template>
