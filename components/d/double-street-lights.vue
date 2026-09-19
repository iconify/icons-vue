<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trn51nbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="trn51nbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:double-street-lights" /></template>
