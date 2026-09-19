<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ripyr9y3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ripyr9y3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:great-pyramid" /></template>
