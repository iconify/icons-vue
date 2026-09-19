<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed2g01b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ed2g01b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flamethrower-soldier" /></template>
