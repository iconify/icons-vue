<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxrn6gb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xxrn6gb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ent-mouth" /></template>
