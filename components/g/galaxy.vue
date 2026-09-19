<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmsjq4c-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jmsjq4c-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:galaxy" /></template>
