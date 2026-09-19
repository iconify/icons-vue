<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzlh_1qrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bzlh_1qrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-072" /></template>
