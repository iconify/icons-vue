<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojit29lhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ojit29lhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:holy-grail" /></template>
