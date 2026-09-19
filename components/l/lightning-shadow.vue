<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fowx1obfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fowx1obfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lightning-shadow" /></template>
