<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-8k-equk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-8k-equk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:barbute" /></template>
