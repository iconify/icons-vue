<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1r8h7bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o1r8h7bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:large-dress" /></template>
