<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9zy-db8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q9zy-db8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:colt-m1911" /></template>
