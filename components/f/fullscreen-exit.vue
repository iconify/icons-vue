<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcmd7lykp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rcmd7lykp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:fullscreen-exit" /></template>
