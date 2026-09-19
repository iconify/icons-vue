<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlcijebmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rlcijebmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hand-bag" /></template>
