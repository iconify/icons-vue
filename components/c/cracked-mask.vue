<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7a-0fcly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b7a-0fcly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cracked-mask" /></template>
