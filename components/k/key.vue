<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn5b7v52d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gn5b7v52d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:key" /></template>
