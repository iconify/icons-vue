<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjpxx4_bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jjpxx4_bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:greaves" /></template>
