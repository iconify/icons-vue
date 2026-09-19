<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc-9sqbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tc-9sqbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:architect-mask" /></template>
