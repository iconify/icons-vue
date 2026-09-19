<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-ud_9n5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g-ud_9n5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:battle-axe" /></template>
