<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u33woviru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u33woviru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:handshake-gloss" /></template>
