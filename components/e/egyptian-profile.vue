<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyx-81bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jyx-81bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:egyptian-profile" /></template>
