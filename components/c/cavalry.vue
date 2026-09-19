<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if3scb1kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="if3scb1kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cavalry" /></template>
