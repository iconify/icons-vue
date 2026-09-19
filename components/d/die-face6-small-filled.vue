<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anky5vblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="anky5vblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:die-face6-small-filled" /></template>
