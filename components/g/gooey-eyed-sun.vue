<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu1dbkyxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bu1dbkyxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gooey-eyed-sun" /></template>
