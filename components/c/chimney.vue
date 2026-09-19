<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pna37sb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pna37sb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chimney" /></template>
