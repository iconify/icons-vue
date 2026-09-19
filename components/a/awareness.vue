<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzmhllkwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dzmhllkwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:awareness" /></template>
