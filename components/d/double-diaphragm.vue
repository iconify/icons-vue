<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0i6kdbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c0i6kdbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:double-diaphragm" /></template>
