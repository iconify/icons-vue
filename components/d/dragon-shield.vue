<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-u9t_bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j-u9t_bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dragon-shield" /></template>
