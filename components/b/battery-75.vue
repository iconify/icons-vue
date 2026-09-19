<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmbl014od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mmbl014od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:battery-75" /></template>
