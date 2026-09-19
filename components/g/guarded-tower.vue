<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-l5kbc7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w-l5kbc7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:guarded-tower" /></template>
