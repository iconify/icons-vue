<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcg36hbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bcg36hbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heavy-timer" /></template>
