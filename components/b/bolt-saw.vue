<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpo_vky9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rpo_vky9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bolt-saw" /></template>
