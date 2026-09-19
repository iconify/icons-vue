<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec_0u4bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ec_0u4bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:animal-hide" /></template>
