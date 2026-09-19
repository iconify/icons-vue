<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3-i6v9_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f3-i6v9_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:frog-foot" /></template>
