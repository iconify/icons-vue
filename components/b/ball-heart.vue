<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7om0018w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a7om0018w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ball-heart" /></template>
