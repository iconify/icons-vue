<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vig0qobll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vig0qobll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hiking" /></template>
