<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca-g7ac0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ca-g7ac0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cleaver" /></template>
