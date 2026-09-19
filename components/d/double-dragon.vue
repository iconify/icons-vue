<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in3r41qir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="in3r41qir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:double-dragon" /></template>
