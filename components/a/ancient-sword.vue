<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6wpg2e-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x6wpg2e-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ancient-sword" /></template>
