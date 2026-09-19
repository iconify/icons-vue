<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/com3mo57v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="com3mo57v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gunshot" /></template>
