<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a17q4j8vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a17q4j8vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bullet-impacts" /></template>
