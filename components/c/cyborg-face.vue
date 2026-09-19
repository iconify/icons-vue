<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_o5gub2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v_o5gub2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cyborg-face" /></template>
