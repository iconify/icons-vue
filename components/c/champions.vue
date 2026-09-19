<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skpt2nkzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="skpt2nkzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:champions" /></template>
