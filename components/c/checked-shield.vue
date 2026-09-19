<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdr_rfb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mdr_rfb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:checked-shield" /></template>
