<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbn6_er5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cbn6_er5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:arena" /></template>
