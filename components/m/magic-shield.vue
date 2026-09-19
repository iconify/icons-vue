<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2w4e9bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a2w4e9bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:magic-shield" /></template>
