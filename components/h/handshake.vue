<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7ltfrc_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f7ltfrc_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:handshake" /></template>
