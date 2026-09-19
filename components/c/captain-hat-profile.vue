<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dde3bnu6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dde3bnu6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:captain-hat-profile" /></template>
