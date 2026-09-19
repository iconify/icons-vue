<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdlk1kkcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bdlk1kkcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:apple-core" /></template>
