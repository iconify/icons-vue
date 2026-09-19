<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tffa9ggeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tffa9ggeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lotus" /></template>
