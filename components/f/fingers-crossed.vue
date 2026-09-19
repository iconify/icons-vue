<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzvbmsb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xzvbmsb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fingers-crossed" /></template>
