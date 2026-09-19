<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss2drd55i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ss2drd55i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:blade-fall" /></template>
