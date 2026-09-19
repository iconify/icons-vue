<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr_8bt_rk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sr_8bt_rk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bookmark" /></template>
