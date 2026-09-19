<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p62ciobpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p62ciobpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chalk-outline-murder" /></template>
