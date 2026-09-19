<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxmka4bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qxmka4bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mad-scientist" /></template>
