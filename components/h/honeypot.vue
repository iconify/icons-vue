<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oul4phlqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oul4phlqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:honeypot" /></template>
