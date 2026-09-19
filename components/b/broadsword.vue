<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqix46bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aqix46bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:broadsword" /></template>
