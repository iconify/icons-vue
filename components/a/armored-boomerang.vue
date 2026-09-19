<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mirs3rtjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mirs3rtjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:armored-boomerang" /></template>
