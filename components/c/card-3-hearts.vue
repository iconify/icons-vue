<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btvll5bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="btvll5bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-3-hearts" /></template>
