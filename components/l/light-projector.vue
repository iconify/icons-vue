<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1j77pbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x1j77pbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:light-projector" /></template>
