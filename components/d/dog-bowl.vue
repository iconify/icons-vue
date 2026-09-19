<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocs8y_blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ocs8y_blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dog-bowl" /></template>
